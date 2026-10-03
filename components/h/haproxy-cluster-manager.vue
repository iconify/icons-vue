<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0g6_mb0d.css';
import '../../css/d/d_rjh4bog.css';
import '../../css/f/f45d-jb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i0g6_mb0d"/><path class="d_rjh4bog"/><circle class="f45d-jb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:haproxy-cluster-manager" /></template>
