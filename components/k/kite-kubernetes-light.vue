<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orm_nmwie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="orm_nmwie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kite-kubernetes-light" /></template>
