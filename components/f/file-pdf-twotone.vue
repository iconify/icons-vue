<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-mbohzae.css';
import '../../css/n/nwge02l1w.css';
import '../../css/j/jcc0dqbjn.css';
import '../../css/j/jso3jy2en.css';
import '../../css/l/l-j_e7brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="h-mbohzae"/><path class="nwge02l1w"/><path class="jcc0dqbjn"/><path class="jso3jy2en"/><path class="l-j_e7brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-pdf-twotone" /></template>
