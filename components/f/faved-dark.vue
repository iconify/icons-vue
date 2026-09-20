<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5gn_5b0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c5gn_5b0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:faved-dark" /></template>
