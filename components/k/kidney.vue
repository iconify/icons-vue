<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu3r8obcb.css';
import '../../css/n/nh9_vbc8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="wu3r8obcb"/><path class="nh9_vbc8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:kidney" /></template>
