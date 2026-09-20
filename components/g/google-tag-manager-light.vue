<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byrz3kh6s.css';
import '../../css/y/y2h-ot9zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="byrz3kh6s"/><path class="y2h-ot9zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-tag-manager-light" /></template>
