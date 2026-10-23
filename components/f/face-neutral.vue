<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9x8dib2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9x8dib2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:face-neutral" /></template>
