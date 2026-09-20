<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdt-6nblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdt-6nblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-cent" /></template>
