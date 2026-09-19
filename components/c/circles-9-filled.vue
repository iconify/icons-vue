<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0k_uub0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0k_uub0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:circles-9-filled" /></template>
