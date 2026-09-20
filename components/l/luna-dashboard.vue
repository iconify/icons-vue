<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uan11fboz.css';
import '../../css/n/ng3jq3bxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uan11fboz"/><path class="ng3jq3bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:luna-dashboard" /></template>
