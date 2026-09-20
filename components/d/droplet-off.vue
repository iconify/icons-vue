<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al3ffg0_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="al3ffg0_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:droplet-off" /></template>
