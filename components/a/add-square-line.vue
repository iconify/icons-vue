<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbho9sbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbho9sbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:add-square-line" /></template>
