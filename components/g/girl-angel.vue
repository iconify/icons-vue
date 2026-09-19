<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqlv_3b2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bqlv_3b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:girl-angel" /></template>
