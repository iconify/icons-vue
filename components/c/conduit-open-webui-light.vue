<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mql_dwhrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mql_dwhrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:conduit-open-webui-light" /></template>
