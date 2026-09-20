<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnadv3bfh.css';
import '../../css/j/j0xz4wbzw.css';
import '../../css/d/d0e6wcchp.css';
import '../../css/u/usnw-tagi.css';
import '../../css/x/xjuqwibjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="bnadv3bfh"/><path class="j0xz4wbzw"/><path class="d0e6wcchp"/><path class="usnw-tagi"/><path class="xjuqwibjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:forauth" /></template>
