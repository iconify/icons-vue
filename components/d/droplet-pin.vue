<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdg6c3btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdg6c3btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:droplet-pin" /></template>
