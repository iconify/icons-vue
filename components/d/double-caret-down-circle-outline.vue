<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq482vr_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lq482vr_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:double-caret-down-circle-outline" /></template>
