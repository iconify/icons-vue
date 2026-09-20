<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8ian1c-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8ian1c-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bottle-tonic-plus" /></template>
