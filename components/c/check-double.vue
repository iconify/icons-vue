<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9eje8s8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y9eje8s8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:check-double" /></template>
