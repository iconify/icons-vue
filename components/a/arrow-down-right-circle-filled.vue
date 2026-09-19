<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frbvlobom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frbvlobom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down-right-circle-filled" /></template>
