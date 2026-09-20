<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyxtbxvey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qyxtbxvey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:atomic-crm-dark" /></template>
