<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soz38ybee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="soz38ybee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:carrot-outline" /></template>
