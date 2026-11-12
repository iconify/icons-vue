<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz7iaspvb.css';
import '../../css/y/y2h-ot9zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oz7iaspvb"/><path class="y2h-ot9zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-tag-manager-light" /></template>
