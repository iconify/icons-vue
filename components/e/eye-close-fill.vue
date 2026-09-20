<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef_udb4nv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef_udb4nv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:eye-close-fill" /></template>
