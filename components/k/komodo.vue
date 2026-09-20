<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8a9mj15s.css';
import '../../css/r/rf0yx6n_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o8a9mj15s"/><path class="rf0yx6n_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:komodo" /></template>
