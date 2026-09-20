<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n98b-3b2e.css';
import '../../css/a/adak2ebid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n98b-3b2e"/><path class="adak2ebid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:budgetbee" /></template>
