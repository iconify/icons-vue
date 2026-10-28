<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f018v5y4u.css';
import '../../css/r/rofz_96kq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f018v5y4u"/><path class="rofz_96kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fileflows-forge-light" /></template>
