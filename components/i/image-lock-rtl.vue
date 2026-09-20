<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fizxgs--e.css';
import '../../css/d/dkx9jnbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fizxgs--e"/><path class="dkx9jnbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:image-lock-rtl" /></template>
