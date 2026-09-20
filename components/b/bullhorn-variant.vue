<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffdp46abo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffdp46abo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bullhorn-variant" /></template>
