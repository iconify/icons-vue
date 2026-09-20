<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-szn7-xv.css';
import '../../css/q/qtp0labzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-szn7-xv"/><path class="qtp0labzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-removed-24" /></template>
