<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1ejs8-4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1ejs8-4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:grease-pencil" /></template>
