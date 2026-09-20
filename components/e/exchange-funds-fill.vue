<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw8u_cvdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw8u_cvdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:exchange-funds-fill" /></template>
