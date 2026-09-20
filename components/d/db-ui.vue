<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qksq_ubpp.css';
import '../../css/d/d1oljg_vw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qksq_ubpp"/><path class="d1oljg_vw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:db-ui" /></template>
