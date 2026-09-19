<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dub6k1bkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dub6k1bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:droplet-bottle-alt-outline" /></template>
