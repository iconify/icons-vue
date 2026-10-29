<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6gh793zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6gh793zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:banknote-solid" /></template>
