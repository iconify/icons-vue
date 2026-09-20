<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-eww7bvd.css';
import '../../css/y/y18qkbg3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l-eww7bvd"/><path class="y18qkbg3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:domain-locker-dark" /></template>
