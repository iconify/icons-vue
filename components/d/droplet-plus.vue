<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6_vswb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6_vswb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:droplet-plus" /></template>
