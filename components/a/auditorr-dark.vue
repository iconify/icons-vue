<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz_yk6bme.css';
import '../../css/e/eig7_3bqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qz_yk6bme"/><path class="eig7_3bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:auditorr-dark" /></template>
