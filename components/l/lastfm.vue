<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5yi_xb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s5yi_xb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:lastfm" /></template>
