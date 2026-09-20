<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7issnsim.css';
import '../../css/p/ptak6-b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7issnsim"/><path class="ptak6-b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:issue-tracks-24" /></template>
