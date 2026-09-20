<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7jn51b8w.css';
import '../../css/v/vrnfpbw3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="r7jn51b8w"/><path class="vrnfpbw3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:certimate" /></template>
