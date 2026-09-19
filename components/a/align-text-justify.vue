<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io1nb8brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io1nb8brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:align-text-justify" /></template>
