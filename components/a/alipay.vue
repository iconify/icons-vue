<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm0c_-b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nm0c_-b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:alipay" /></template>
