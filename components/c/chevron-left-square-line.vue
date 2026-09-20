<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmluf-e8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmluf-e8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:chevron-left-square-line" /></template>
