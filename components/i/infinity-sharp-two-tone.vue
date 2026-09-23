<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4dwjys8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4dwjys8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:infinity-sharp-two-tone" /></template>
