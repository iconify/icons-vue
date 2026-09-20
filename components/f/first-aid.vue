<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnl04-bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-3};
const content = `<path class="qnl04-bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:first-aid" /></template>
