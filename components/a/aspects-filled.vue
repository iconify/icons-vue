<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykalgvbci.css';
import '../../css/y/yn92p7rip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ykalgvbci"/><path class="yn92p7rip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:aspects-filled" /></template>
