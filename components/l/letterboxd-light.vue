<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np_e4lx1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="np_e4lx1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:letterboxd-light" /></template>
