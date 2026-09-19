<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpct6ubfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpct6ubfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:book-library-filled" /></template>
