<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc_cn3gik.css';
import '../../css/f/fd3h4yb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rc_cn3gik"/><path class="fd3h4yb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gdms-light" /></template>
