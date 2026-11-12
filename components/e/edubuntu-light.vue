<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbjad6brt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pbjad6brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:edubuntu-light" /></template>
