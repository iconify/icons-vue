<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avd1rxbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="avd1rxbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:alipay" /></template>
