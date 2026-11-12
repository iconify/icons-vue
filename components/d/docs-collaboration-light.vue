<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzk01q4nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kzk01q4nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docs-collaboration-light" /></template>
