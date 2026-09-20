<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn412pbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qn412pbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:komodo-light" /></template>
