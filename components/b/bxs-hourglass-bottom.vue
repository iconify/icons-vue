<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s79r90nvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s79r90nvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-hourglass-bottom" /></template>
