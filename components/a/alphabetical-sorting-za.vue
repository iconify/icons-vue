<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw_7llbhm.css';
import '../../css/e/egp4naccw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zw_7llbhm"/><path class="egp4naccw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:alphabetical-sorting-za" /></template>
