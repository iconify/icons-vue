<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf-55cwyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf-55cwyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fan-direction-up-fill" /></template>
