<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvifft_3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvifft_3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:ambulance-clock" /></template>
