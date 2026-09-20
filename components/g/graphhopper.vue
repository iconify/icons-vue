<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj0ca7rqc.css';
import '../../css/i/ip_aiub7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="bj0ca7rqc"/><path class="ip_aiub7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:graphhopper" /></template>
