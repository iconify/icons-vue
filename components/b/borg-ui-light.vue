<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bff3rizlq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bff3rizlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:borg-ui-light" /></template>
