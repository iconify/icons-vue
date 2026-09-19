<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpr0hcbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mpr0hcbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-seven-small-filled" /></template>
