<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgt-rix9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bgt-rix9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:focalboard-dark" /></template>
