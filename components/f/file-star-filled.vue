<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdv2q9x8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdv2q9x8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:file-star-filled" /></template>
