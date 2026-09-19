<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li_aurb-v.css';
import '../../css/q/qv-j8ebyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="li_aurb-v"/><path class="qv-j8ebyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-card" /></template>
