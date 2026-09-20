<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/borcvuv3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="borcvuv3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:coffee" /></template>
