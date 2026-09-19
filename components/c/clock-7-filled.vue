<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl2-epb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl2-epb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:clock-7-filled" /></template>
