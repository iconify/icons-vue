<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt4z2i14a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nt4z2i14a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ephemera" /></template>
