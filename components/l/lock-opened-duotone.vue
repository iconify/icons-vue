<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frndcpb0j.css';
import '../../css/t/tn4b2zsid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frndcpb0j"/><path class="tn4b2zsid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:lock-opened-duotone" /></template>
