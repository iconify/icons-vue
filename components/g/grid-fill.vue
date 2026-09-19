<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl-ql3bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl-ql3bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:grid-fill" /></template>
