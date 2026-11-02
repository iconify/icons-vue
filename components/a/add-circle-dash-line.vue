<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3vh1xbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3vh1xbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:add-circle-dash-line" /></template>
