<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vro_2gb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vro_2gb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circles-sharp" /></template>
