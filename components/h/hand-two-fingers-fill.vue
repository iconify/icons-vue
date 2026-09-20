<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfjtfmw_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hfjtfmw_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hand-two-fingers-fill" /></template>
