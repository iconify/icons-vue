<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyeglmmtr.css';
import '../../css/a/akc_yvbhb.css';
import '../../css/u/ua_s72b4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eyeglmmtr"/><path class="akc_yvbhb"/><path class="ua_s72b4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dockflare-dark" /></template>
