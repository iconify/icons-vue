<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkumzcb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkumzcb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:clockify" /></template>
