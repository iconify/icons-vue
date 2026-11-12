<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrflbhmmb.css';
import '../../css/y/y_pmmmb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xrflbhmmb"/><circle class="y_pmmmb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:livinity-dark" /></template>
