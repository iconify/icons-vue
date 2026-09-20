<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kksua50ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kksua50ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gitsave-light" /></template>
