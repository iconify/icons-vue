<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu3v3lbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu3v3lbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:droplet-key" /></template>
