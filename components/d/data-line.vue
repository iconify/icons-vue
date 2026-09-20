<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omswqobfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omswqobfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:data-line" /></template>
