<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfgy3dwww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfgy3dwww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:credit-card-sharp" /></template>
