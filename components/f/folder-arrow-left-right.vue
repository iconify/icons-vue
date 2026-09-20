<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyvkl8e2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyvkl8e2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-arrow-left-right" /></template>
