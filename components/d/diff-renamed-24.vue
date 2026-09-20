<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m46eym3cb.css';
import '../../css/i/i-yovpx2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m46eym3cb"/><path class="i-yovpx2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:diff-renamed-24" /></template>
