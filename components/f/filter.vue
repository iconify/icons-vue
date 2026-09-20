<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao_6u9ujf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao_6u9ujf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter" /></template>
