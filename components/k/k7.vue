<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/une0tkb_h.css';
import '../../css/z/zxjr-cemx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="une0tkb_h"/><path class="zxjr-cemx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:k7" /></template>
