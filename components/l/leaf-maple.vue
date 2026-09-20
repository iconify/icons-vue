<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kudks89uf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kudks89uf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:leaf-maple" /></template>
