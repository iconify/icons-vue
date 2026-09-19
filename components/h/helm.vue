<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmwadnbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jmwadnbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:helm" /></template>
