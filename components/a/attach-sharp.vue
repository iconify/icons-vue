<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztfbiebtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ztfbiebtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:attach-sharp" /></template>
