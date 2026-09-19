<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu22mfb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="hu22mfb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bot-generic-26" /></template>
