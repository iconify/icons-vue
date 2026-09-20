<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fae7j8bsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fae7j8bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:clipboard-check-line" /></template>
