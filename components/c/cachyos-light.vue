<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojfp7w8vt.css';
import '../../css/s/sf89cnbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ojfp7w8vt"/><path class="sf89cnbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cachyos-light" /></template>
