<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md81p0dal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="md81p0dal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linuxgsm-light" /></template>
