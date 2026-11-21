<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxh80gbuf.css';
import '../../css/f/fj4fd9bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxh80gbuf"/><path class="fj4fd9bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-backup-filled" /></template>
