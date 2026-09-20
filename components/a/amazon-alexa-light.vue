<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdcjikb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gdcjikb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-alexa-light" /></template>
