<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okzgdh2-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okzgdh2-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:layer-arrow-down" /></template>
