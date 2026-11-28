<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofkb0xw0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofkb0xw0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-up-narrow-wide-solid" /></template>
