<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osuby9bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osuby9bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:backburger" /></template>
