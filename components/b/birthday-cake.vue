<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzvekvb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzvekvb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:birthday-cake" /></template>
