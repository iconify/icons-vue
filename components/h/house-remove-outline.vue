<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbxakcdnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbxakcdnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-remove-outline" /></template>
