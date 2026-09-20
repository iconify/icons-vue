<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agqa6qbci.css';
import '../../css/i/ic7d043zq.css';
import '../../css/k/kcldt_bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="agqa6qbci"/><path class="ic7d043zq"/><path class="kcldt_bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-intensive-care" /></template>
