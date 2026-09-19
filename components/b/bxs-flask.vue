<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7xvukb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7xvukb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-flask" /></template>
