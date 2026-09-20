<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wli5199pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wli5199pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:coinbase" /></template>
