<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_2n6bbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b_2n6bbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:keila-light" /></template>
