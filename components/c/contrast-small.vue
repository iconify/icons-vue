<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyqdm1i2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dyqdm1i2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:contrast-small" /></template>
