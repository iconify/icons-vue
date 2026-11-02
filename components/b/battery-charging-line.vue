<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxrtyqdeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxrtyqdeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-charging-line" /></template>
