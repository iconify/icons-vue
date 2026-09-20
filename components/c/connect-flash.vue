<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roj7v4bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="roj7v4bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:connect-flash" /></template>
