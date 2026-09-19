<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0b9nfbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k0b9nfbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:gavel" /></template>
