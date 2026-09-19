<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p29-zfr-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p29-zfr-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:ampl" /></template>
