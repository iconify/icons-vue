<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqb7r5b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqb7r5b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:droplet-off" /></template>
