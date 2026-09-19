<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqy2g75wd.css';
import '../../css/b/bm9qtjbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bqy2g75wd"/><path class="bm9qtjbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:alert-circle-sharp" /></template>
