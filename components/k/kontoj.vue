<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agda5ibxs.css';
import '../../css/n/nfv5mkb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="agda5ibxs"/><path class="nfv5mkb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kontoj" /></template>
