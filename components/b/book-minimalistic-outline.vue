<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iep4jyacq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iep4jyacq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:book-minimalistic-outline" /></template>
