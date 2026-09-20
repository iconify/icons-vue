<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tovo4ccsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tovo4ccsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-settings" /></template>
