<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um9s7iazo.css';
import '../../css/n/npuhol_7o.css';
import '../../css/f/f7wi88xzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="um9s7iazo"/><path class="npuhol_7o"/><path class="f7wi88xzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:f-droid-light" /></template>
