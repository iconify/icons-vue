<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cep5rxtrl.css';
import '../../css/s/syec1nbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="cep5rxtrl"/><path class="syec1nbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbbudget" /></template>
