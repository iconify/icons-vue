<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dja5gvbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dja5gvbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-kiss-wink-heart" /></template>
