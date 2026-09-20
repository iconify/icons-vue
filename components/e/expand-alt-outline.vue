<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi6e-ccrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yi6e-ccrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:expand-alt-outline" /></template>
