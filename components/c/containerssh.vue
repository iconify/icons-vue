<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpptukm0u.css';
import '../../css/b/bkvywwbqo.css';
import '../../css/y/ypxrjb7gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qpptukm0u"/><path class="bkvywwbqo"/><path class="ypxrjb7gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:containerssh" /></template>
