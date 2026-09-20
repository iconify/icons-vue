<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu943_v5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu943_v5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:droplet-cog" /></template>
