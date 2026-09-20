<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuqfn8y1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nuqfn8y1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:google-play" /></template>
