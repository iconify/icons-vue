<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv_brepse.css';
import '../../css/t/tw3byrbcp.css';
import '../../css/b/b6qqbxbne.css';
import '../../css/d/dspl_gbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yv_brepse"/><path class="tw3byrbcp"/><path class="b6qqbxbne"/><path class="dspl_gbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:dollar-circle-twotone" /></template>
