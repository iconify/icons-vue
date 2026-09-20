<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr5e5_blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fr5e5_blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:itunes-note" /></template>
