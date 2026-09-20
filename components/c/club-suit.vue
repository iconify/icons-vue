<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq_xn5bxe.css';
import '../../css/s/snp287xku.css';
import '../../css/o/obr8ke7yg.css';
import '../../css/h/h_tc_qcyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xq_xn5bxe"/><path class="snp287xku"/><path class="obr8ke7yg"/><path class="h_tc_qcyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:club-suit" /></template>
