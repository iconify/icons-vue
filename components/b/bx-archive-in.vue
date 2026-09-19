<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwj-tdbmb.css';
import '../../css/k/k4o7aepui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwj-tdbmb"/><path class="k4o7aepui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-archive-in" /></template>
