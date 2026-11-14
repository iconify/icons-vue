<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kievrdbdp.css';
import '../../css/n/nstbe3bzr.css';
import '../../css/u/uln8bqb4e.css';
import '../../css/z/z0qdkwbtn.css';
import '../../css/i/ip9tdh1yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kievrdbdp"/><path class="nstbe3bzr"/><path class="uln8bqb4e"/><path class="z0qdkwbtn"/><path class="ip9tdh1yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:haproxy" /></template>
