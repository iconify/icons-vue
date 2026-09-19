<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slr52vb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slr52vb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:handheld-filled" /></template>
