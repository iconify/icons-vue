<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io9pepb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io9pepb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hanger-broken" /></template>
