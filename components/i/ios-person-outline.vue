<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsit_hb8q.css';
import '../../css/k/kdqm06bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xsit_hb8q"/><path class="kdqm06bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-person-outline" /></template>
