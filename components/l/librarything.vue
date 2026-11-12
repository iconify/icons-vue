<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq-vo4ugb.css';
import '../../css/x/xtkshpbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uq-vo4ugb"/><path class="xtkshpbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:librarything" /></template>
