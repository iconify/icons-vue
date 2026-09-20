<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loj74m4-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="loj74m4-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freedombox-dark" /></template>
