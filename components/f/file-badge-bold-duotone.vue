<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgissgbda.css';
import '../../css/w/w1wl29bmf.css';
import '../../css/c/ckoc0pbbx.css';
import '../../css/x/x4f46-b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgissgbda"/><path class="w1wl29bmf"/><path class="ckoc0pbbx"/><path class="x4f46-b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-badge-bold-duotone" /></template>
