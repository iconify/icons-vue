<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-j2tshyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="h-j2tshyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:edit-solid-mirrored-12" /></template>
