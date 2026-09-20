<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbxra6t0y.css';
import '../../css/s/sm4k7rbaa.css';
import '../../css/m/mg66m1bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xbxra6t0y"/><path class="sm4k7rbaa"/><path class="mg66m1bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hivemq" /></template>
