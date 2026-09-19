<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-cy1ebpm.css';
import '../../css/m/miw977k3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d-cy1ebpm"/><path class="miw977k3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-box" /></template>
