<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_9v2_b2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s_9v2_b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bed-single-filled" /></template>
