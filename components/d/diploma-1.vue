<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npewmlxrc.css';
import '../../css/u/unp6fccbt.css';
import '../../css/n/na_wzcctt.css';
import '../../css/e/e4sbecbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="npewmlxrc"/><path class="unp6fccbt"/><path class="na_wzcctt"/><path class="e4sbecbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:diploma-1" /></template>
