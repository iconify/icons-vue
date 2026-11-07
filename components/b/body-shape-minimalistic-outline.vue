<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm92yt0_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hm92yt0_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:body-shape-minimalistic-outline" /></template>
