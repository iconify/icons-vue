<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twoyz1r4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twoyz1r4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-sun-sharp" /></template>
