<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leafxacrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="leafxacrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:book-open" /></template>
