<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6nl0kb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6nl0kb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:filter-mail-edit" /></template>
