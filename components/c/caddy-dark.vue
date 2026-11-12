<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpdkwn6lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mpdkwn6lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:caddy-dark" /></template>
