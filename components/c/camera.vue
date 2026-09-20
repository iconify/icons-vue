<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syqfetb6n.css';
import '../../css/l/lkky-nhlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="syqfetb6n"/><path class="lkky-nhlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:camera" /></template>
