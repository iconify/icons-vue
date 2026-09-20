<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyyv7kb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fyyv7kb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hetzner-light" /></template>
