<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv9yq260v.css';
import '../../css/s/ssgj37swb.css';
import '../../css/c/cy8jwyroj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uv9yq260v"/><path class="ssgj37swb"/><path class="cy8jwyroj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:diode-48" /></template>
