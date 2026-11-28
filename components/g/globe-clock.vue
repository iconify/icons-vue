<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km9rw_16t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km9rw_16t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:globe-clock" /></template>
