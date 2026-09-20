<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inf7f8bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inf7f8bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bell-plus-sharp" /></template>
