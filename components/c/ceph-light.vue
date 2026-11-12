<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wya1714qm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wya1714qm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ceph-light" /></template>
