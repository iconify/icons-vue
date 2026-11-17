<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmsoejb8x.css';
import '../../css/z/zltcmzqac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mmsoejb8x"/><circle class="zltcmzqac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cadenza" /></template>
