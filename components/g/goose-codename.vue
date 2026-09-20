<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc2s802al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc2s802al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:goose-codename" /></template>
