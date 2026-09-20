<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj9bwkiqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj9bwkiqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:flat" /></template>
