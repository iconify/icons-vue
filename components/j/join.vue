<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj8nchxay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="qj8nchxay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:join" /></template>
