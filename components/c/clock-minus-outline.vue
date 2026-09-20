<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhyluob_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhyluob_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-minus-outline" /></template>
