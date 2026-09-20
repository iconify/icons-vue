<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou2dp-ouw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou2dp-ouw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lifebuoy" /></template>
