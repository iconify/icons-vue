<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-77kf30t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o-77kf30t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filedrop-dark" /></template>
