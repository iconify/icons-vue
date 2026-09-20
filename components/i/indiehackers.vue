<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3-66vhye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3-66vhye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:indiehackers" /></template>
