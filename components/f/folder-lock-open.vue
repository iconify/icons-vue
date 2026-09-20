<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciql3ubgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ciql3ubgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-lock-open" /></template>
