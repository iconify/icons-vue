<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbvk0jbkh.css';
import '../../css/s/sxrldrbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sbvk0jbkh"/><path class="sxrldrbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hyperhdr" /></template>
