<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx_-4nu-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qx_-4nu-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:logto-light" /></template>
