<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc7jjcb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qc7jjcb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:folo-light" /></template>
