<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dosrg5bml.css';
import '../../css/d/djaim6bic.css';
import '../../css/m/mp4dc4cxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dosrg5bml"/><path class="djaim6bic"/><path class="mp4dc4cxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ghostty" /></template>
