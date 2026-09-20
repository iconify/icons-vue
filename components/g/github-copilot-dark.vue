<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwuo3q2qx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pwuo3q2qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:github-copilot-dark" /></template>
