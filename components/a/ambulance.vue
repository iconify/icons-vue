<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bju99-9zx.css';
import '../../css/p/pl4wrbb3x.css';
import '../../css/y/yhlbi21sm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bju99-9zx"/><path class="pl4wrbb3x"/><path class="yhlbi21sm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:ambulance" /></template>
