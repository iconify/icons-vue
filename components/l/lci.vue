<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p34v2-8-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p34v2-8-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lci" /></template>
