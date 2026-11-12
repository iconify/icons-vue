<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvxobsbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gvxobsbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hook0-light" /></template>
