<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dseb0nhyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dseb0nhyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fullscreen-2" /></template>
