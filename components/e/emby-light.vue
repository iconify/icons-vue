<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4qt0-s2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o4qt0-s2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:emby-light" /></template>
