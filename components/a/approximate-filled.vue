<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is1rkcbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="is1rkcbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:approximate-filled" /></template>
