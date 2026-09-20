<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfdi0b5fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfdi0b5fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:arrow-thick-left-3-bold" /></template>
