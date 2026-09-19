<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxc_y7qso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":424};
const content = `<path class="pxc_y7qso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:card-off" /></template>
