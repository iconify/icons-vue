<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmg31mbbr.css';
import '../../css/y/yq4ktg_2p.css';
import '../../css/q/qxwq8bcbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wmg31mbbr"/><path class="yq4ktg_2p"/><path class="qxwq8bcbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-manager-light" /></template>
