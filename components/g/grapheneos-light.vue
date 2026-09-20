<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1g1ml97w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u1g1ml97w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grapheneos-light" /></template>
