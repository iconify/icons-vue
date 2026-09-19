<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c61g_vb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c61g_vb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-right-1-duotone" /></template>
