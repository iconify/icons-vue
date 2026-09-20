<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h120-nbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h120-nbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:instapods-dark" /></template>
