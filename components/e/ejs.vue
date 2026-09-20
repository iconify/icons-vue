<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpmggy3dl.css';
import '../../css/a/axgi99bgf.css';
import '../../css/b/b_pdi8qgn.css';
import '../../css/k/kjy2ryjzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpmggy3dl"/><path class="axgi99bgf"/><path class="b_pdi8qgn"/><path clip-rule="evenodd" class="kjy2ryjzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ejs" /></template>
