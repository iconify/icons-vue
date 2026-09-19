<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh1cukqij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oh1cukqij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:align-objects-middle" /></template>
