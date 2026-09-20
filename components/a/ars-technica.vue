<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3fm6ybam.css';
import '../../css/t/tegirhu2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="f3fm6ybam"/><path class="tegirhu2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ars-technica" /></template>
