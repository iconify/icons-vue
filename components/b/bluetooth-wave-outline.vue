<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb6shej8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sb6shej8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bluetooth-wave-outline" /></template>
