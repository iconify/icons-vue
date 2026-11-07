<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spcglef6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="spcglef6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-down-outline" /></template>
