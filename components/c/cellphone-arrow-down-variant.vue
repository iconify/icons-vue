<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnvy57b8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnvy57b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cellphone-arrow-down-variant" /></template>
