<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqvk9et-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqvk9et-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hook" /></template>
