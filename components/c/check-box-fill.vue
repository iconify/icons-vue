<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz-3kdwdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hz-3kdwdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:check-box-fill" /></template>
