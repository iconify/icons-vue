<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuun1mbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cuun1mbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-crack-outline" /></template>
