<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-w6i4z_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g-w6i4z_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:librephotos-light" /></template>
