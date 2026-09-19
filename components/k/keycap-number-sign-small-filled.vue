<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4b2i8bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="u4b2i8bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-number-sign-small-filled" /></template>
