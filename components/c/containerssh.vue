<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpptukm0u.css';
import '../../css/b/bkvywwbqo.css';
import '../../css/t/t1b1reb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qpptukm0u"/><path class="bkvywwbqo"/><path class="t1b1reb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:containerssh" /></template>
