<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_4ve6b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_4ve6b5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:hand-pointer-line" /></template>
