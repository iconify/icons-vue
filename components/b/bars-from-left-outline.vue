<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq04mtb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq04mtb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:bars-from-left-outline" /></template>
