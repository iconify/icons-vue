<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6bpd94xk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v6bpd94xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:iplayarr-light" /></template>
