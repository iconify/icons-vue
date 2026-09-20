<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x512z4xmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x512z4xmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dailydotdev" /></template>
