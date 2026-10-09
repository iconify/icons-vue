<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2pyevbzu.css';
import '../../css/n/n4-5ir_js.css';
import '../../css/m/maa-xwdby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g2pyevbzu"/><path class="n4-5ir_js"/><path class="maa-xwdby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:delete-20" /></template>
