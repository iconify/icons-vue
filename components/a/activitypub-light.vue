<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2rd6hb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k2rd6hb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:activitypub-light" /></template>
