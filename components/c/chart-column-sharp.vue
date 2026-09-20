<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ossksxb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ossksxb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-column-sharp" /></template>
