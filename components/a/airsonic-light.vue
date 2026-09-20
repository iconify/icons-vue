<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm9w7kb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tm9w7kb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:airsonic-light" /></template>
