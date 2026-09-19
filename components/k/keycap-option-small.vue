<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8a072jfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="h8a072jfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-option-small" /></template>
