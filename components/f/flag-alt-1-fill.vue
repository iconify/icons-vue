<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2irib6yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2irib6yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:flag-alt-1-fill" /></template>
