<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds05xy4_w.css';
import '../../css/f/fwkrdacaj.css';
import '../../css/q/qo_hhtb9e.css';
import '../../css/x/xqd5dlbow.css';
import '../../css/a/a5bc86osr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ds05xy4_w"/><path class="fwkrdacaj"/><path class="qo_hhtb9e"/><path class="xqd5dlbow"/><path class="a5bc86osr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:automatic1111-light" /></template>
