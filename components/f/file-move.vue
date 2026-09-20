<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yml1xpbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yml1xpbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-move" /></template>
