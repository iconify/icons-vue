<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkia4r3ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkia4r3ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ghost-gloss" /></template>
