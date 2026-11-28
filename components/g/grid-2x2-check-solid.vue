<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv7a538cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv7a538cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:grid-2x2-check-solid" /></template>
