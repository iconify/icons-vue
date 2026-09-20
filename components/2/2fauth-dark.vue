<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb2ayacaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rb2ayacaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:2fauth-dark" /></template>
