<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg1m8dbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jg1m8dbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:error" /></template>
