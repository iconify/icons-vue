<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm0-mtg3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm0-mtg3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ariakit" /></template>
