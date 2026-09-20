<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz274dbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pz274dbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dagu-light" /></template>
