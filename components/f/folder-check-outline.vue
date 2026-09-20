<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkty1mbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkty1mbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-check-outline" /></template>
