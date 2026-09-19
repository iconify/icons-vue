<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqh7qq44e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqh7qq44e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-long-down" /></template>
