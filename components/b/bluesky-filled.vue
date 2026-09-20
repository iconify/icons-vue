<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7ue-g.css';
import '../../css/s/so-from-76.css';
import '../../css/f/fill-to-1.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7ue-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:bluesky-filled" /></template>
