<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn2jjfs2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gn2jjfs2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:info-circle" /></template>
