<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaivjhz7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yaivjhz7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-skip-next" /></template>
