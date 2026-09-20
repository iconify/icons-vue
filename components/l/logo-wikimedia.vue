<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpgnasd1n.css';
import '../../css/p/psgevsbih.css';
import '../../css/g/gs86xrbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xpgnasd1n"/><path class="psgevsbih"/><circle class="gs86xrbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:logo-wikimedia" /></template>
