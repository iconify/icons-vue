<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwhpnrv1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":472};
const content = `<path class="iwhpnrv1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:cookie" /></template>
