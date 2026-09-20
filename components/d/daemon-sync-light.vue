<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyxxv8bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zyxxv8bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:daemon-sync-light" /></template>
