<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm91581ko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wm91581ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:loglynx-light" /></template>
