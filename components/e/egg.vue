<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy6_4mxhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy6_4mxhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:egg" /></template>
