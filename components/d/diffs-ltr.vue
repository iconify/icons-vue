<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_u8qmzuo.css';
import '../../css/l/lkmselk-n.css';
import '../../css/l/lsxdb1s3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q_u8qmzuo"/><path class="lkmselk-n"/><path class="lsxdb1s3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:diffs-ltr" /></template>
