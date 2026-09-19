<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xobthpb_z.css';
import '../../css/l/ld5kc0m-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xobthpb_z"/><path class="ld5kc0m-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:arrow-forward-circle-outline" /></template>
