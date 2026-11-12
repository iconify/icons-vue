<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbiaeacws.css';
import '../../css/h/hjy0wjyzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mbiaeacws"/><path class="hjy0wjyzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fileflows-forge-dark" /></template>
