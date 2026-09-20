<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy8dm9bqf.css';
import '../../css/h/hdhbc3z4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sy8dm9bqf"/><path class="hdhbc3z4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frankmd-light" /></template>
