<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa_y8xbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xa_y8xbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:atomic-crm-light" /></template>
