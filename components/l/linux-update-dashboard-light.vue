<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg35-r2sk.css';
import '../../css/i/ieqeobcsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vg35-r2sk"/><path class="ieqeobcsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linux-update-dashboard-light" /></template>
