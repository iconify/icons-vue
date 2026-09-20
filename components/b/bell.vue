<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb_bkrocs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rb_bkrocs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:bell" /></template>
