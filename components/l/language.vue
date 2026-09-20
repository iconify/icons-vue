<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr-mobb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr-mobb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:language" /></template>
