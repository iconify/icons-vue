<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs91p4brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs91p4brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:clipboard-plus-filled" /></template>
