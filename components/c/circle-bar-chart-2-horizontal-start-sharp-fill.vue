<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu97xdbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wu97xdbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-bar-chart-2-horizontal-start-sharp-fill" /></template>
