<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve51lgbsq.css';
import '../../css/d/d2k80oitw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ve51lgbsq"/><path class="d2k80oitw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:bug-twotone" /></template>
