<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk-ucv3un.css';
import '../../css/e/ek9bptpxf.css';
import '../../css/v/vek2qqbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk-ucv3un"/><path class="ek9bptpxf"/><path class="vek2qqbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:maha" /></template>
