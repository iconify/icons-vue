<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sml5s9xuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sml5s9xuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrows-up-down-expressive" /></template>
