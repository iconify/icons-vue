<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kof1pjl2v.css';
import '../../css/w/w6rc0es0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kof1pjl2v"/><path class="w6rc0es0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:balance-scale" /></template>
