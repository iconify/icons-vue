<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv1e5xb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wv1e5xb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:heart-filled" /></template>
