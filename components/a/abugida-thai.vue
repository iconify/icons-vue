<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7w72dyhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7w72dyhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:abugida-thai" /></template>
