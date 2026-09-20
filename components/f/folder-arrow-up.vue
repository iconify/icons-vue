<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4c77e6cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4c77e6cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-arrow-up" /></template>
