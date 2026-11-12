<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpn4e3smv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bpn4e3smv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hermesseg-light" /></template>
