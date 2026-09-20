<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp4zgl_dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dp4zgl_dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:inexogy-dark" /></template>
