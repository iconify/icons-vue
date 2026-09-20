<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpkia7k9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpkia7k9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:location-cog" /></template>
