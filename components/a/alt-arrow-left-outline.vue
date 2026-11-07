<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3t23s65d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s3t23s65d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-left-outline" /></template>
