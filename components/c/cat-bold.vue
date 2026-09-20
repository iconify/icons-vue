<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3us1om-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l3us1om-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cat-bold" /></template>
