<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glpy9wu7t.css';
import '../../css/t/tr_qzvbuu.css';
import '../../css/f/fd6xyabdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="glpy9wu7t"><path class="tr_qzvbuu"/><circle class="fd6xyabdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:lable-duotone" /></template>
