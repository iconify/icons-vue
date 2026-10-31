<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/k/kioy7272c.css';
import '../../css/q/qg3owvukv.css';
import '../../css/o/ooj8cp7ju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="kioy7272c wm-shadow"/><path class="qg3owvukv wm-shadow"/><path class="ooj8cp7ju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:chevron-last" /></template>
