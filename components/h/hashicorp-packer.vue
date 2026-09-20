<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvt9z9bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rvt9z9bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-packer" /></template>
