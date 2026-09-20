<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa-vdingl.css';
import '../../css/j/jm-ifbcih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qa-vdingl"/><path class="jm-ifbcih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crt-sh" /></template>
