<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvo458bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvo458bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:clock-12-filled" /></template>
