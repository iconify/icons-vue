<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2pltccts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2pltccts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:info-circle-outline" /></template>
