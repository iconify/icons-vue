<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd2b99bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nd2b99bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-consul-light" /></template>
