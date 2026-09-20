<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7pgh2bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t7pgh2bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:defguard" /></template>
