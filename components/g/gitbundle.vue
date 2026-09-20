<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2766uktk.css';
import '../../css/l/l2dczz-db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l2766uktk"/><path class="l2dczz-db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gitbundle" /></template>
