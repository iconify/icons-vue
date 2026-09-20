<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7lvpblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv7lvpblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-horizontal-cog" /></template>
