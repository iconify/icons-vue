<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caw-axbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caw-axbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:feather-minus-filled" /></template>
