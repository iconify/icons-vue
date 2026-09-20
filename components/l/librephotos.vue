<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydwt8bbeh.css';
import '../../css/x/x5xtfzb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="ydwt8bbeh"/><path class="x5xtfzb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:librephotos" /></template>
