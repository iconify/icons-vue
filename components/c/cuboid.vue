<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io9gf347v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io9gf347v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cuboid" /></template>
