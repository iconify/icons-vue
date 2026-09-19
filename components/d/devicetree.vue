<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7lh0s6zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p7lh0s6zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:devicetree" /></template>
