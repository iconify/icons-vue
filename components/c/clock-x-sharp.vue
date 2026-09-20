<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc7n59pdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc7n59pdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-x-sharp" /></template>
