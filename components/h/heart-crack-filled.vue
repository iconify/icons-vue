<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro6flcd8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro6flcd8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:heart-crack-filled" /></template>
