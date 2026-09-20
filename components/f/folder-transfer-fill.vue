<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo-b3efua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lo-b3efua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-transfer-fill" /></template>
