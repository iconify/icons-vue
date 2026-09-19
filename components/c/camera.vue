<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2pau0bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":24};
const content = `<path class="w2pau0bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:camera" /></template>
