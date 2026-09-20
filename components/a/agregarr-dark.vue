<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uog1-9bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uog1-9bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:agregarr-dark" /></template>
