<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buse0cc_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="buse0cc_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:live-schedule" /></template>
