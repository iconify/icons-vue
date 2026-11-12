<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbhmpbcfb.css';
import '../../css/t/t_72od1sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dbhmpbcfb"/><path class="t_72od1sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aliexpress-light" /></template>
