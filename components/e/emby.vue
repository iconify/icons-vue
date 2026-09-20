<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg_rohbjm.css';
import '../../css/c/cdq24z_9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jg_rohbjm"/><path class="cdq24z_9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:emby" /></template>
