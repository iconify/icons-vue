<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugjfybw6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ugjfybw6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:configclarity-light" /></template>
