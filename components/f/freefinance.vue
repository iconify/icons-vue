<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0ncxjb_s.css';
import '../../css/b/bs_ka8b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v0ncxjb_s"/><path class="bs_ka8b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freefinance" /></template>
