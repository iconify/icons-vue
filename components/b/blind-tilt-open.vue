<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id6amw2pa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id6amw2pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:blind-tilt-open" /></template>
