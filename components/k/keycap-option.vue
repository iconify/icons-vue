<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb9ijrb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hb9ijrb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-option" /></template>
