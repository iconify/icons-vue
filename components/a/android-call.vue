<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlacl_i2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dlacl_i2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-call" /></template>
