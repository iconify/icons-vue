<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt806nbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt806nbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-moon-meatball" /></template>
