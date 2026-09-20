<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lph5zbctn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lph5zbctn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:book-fill" /></template>
