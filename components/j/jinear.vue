<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md_a79lck.css';
import '../../css/d/dwubu5bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="md_a79lck"/><path class="dwubu5bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jinear" /></template>
