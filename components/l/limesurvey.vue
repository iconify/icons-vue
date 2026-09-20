<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-alm_vye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r-alm_vye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:limesurvey" /></template>
