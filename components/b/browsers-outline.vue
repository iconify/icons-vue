<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpbqltkex.css';
import '../../css/m/mkt8b3bpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="wpbqltkex"/><path class="mkt8b3bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:browsers-outline" /></template>
