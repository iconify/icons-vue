<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmvtqzacp.css';
import '../../css/y/yox3j-b4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmvtqzacp"/><path class="yox3j-b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:book" /></template>
