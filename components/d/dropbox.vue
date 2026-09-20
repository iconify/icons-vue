<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sktatzb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sktatzb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dropbox" /></template>
