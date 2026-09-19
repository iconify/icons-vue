<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng-l8i51q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ng-l8i51q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:flag" /></template>
