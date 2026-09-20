<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3zorkblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y3zorkblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:defguard-light" /></template>
