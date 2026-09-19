<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kny6_hb4a.css';
import '../../css/r/rys9nkbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kny6_hb4a"/><path class="rys9nkbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-family" /></template>
