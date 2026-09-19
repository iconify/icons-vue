<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu65d0bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu65d0bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:franceinfo" /></template>
