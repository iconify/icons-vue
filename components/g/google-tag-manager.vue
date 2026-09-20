<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6ue2-jip.css';
import '../../css/y/yy45p2b8q.css';
import '../../css/z/z271pgbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e6ue2-jip"/><path class="yy45p2b8q"/><circle class="z271pgbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-tag-manager" /></template>
