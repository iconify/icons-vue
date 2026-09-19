<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sznxx_but.css';
import '../../css/d/dduzo9-ka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sznxx_but"/><path class="dduzo9-ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:credit-card-1" /></template>
