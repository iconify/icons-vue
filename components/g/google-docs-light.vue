<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obbl1ynnb.css';
import '../../css/j/jj_lj5bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="obbl1ynnb"/><path class="jj_lj5bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-docs-light" /></template>
