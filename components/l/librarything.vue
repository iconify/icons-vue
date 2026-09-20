<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq-vo4ugb.css';
import '../../css/l/lhs-_ebhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uq-vo4ugb"/><path class="lhs-_ebhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:librarything" /></template>
