<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7k168yek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7k168yek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:floor-lantern-off" /></template>
