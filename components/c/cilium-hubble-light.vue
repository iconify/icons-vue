<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy7zh6btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dy7zh6btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cilium-hubble-light" /></template>
