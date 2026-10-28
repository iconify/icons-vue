<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avp4ev5ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="avp4ev5ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hindsight-light" /></template>
