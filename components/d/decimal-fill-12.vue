<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go9655bbx.css';
import '../../css/y/yqefc5upf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<ellipse class="go9655bbx"/><circle class="yqefc5upf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:decimal-fill-12" /></template>
