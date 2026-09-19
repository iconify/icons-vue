<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/y/y6f0jibvm.css';
import '../../css/x/x076sbbwr.css';
import '../../css/d/d7narlrit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="y6f0jibvm"/><path class="x076sbbwr"/><path class="d7narlrit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:arrow-circle-left" /></template>
