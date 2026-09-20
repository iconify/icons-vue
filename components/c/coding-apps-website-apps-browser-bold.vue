<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6xfrmbct.css';
import '../../css/u/u4aylz3fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6xfrmbct"/><path class="u4aylz3fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:coding-apps-website-apps-browser-bold" /></template>
