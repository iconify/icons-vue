<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8tbmnbml.css';
import '../../css/k/kpb0wubyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z8tbmnbml"/><path class="kpb0wubyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:caddy" /></template>
