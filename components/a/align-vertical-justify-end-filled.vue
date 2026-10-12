<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r74w_fbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r74w_fbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:align-vertical-justify-end-filled" /></template>
