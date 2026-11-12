<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-9jh2b_h.css';
import '../../css/l/l2dczz-db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v-9jh2b_h"/><path class="l2dczz-db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gitbundle" /></template>
