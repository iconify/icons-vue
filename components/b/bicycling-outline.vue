<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzwrbprix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mzwrbprix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bicycling-outline" /></template>
