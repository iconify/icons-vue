<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kky9d-ehz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kky9d-ehz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:factory-solid" /></template>
