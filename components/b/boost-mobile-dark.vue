<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv0rwxbnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vv0rwxbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:boost-mobile-dark" /></template>
