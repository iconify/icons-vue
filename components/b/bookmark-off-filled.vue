<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4tca7g_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4tca7g_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bookmark-off-filled" /></template>
