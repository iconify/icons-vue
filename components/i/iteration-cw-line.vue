<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-0o_wjdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-0o_wjdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:iteration-cw-line" /></template>
