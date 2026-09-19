<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l51mozblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l51mozblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bandcamp-filled" /></template>
