<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3ni9_b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3ni9_b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chevrons-right-left-filled" /></template>
