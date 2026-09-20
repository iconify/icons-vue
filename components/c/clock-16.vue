<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qccp3wbhy.css';
import '../../css/b/b2tyl1b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qccp3wbhy"/><path clip-rule="evenodd" class="b2tyl1b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:clock-16" /></template>
