<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umfp6gevz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umfp6gevz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flame-sharp-duotone" /></template>
