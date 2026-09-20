<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2o6txvom.css';
import '../../css/s/syec1nbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="v2o6txvom"/><path class="syec1nbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbbudget" /></template>
