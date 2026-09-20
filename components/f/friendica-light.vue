<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smlw75opn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="smlw75opn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:friendica-light" /></template>
