<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/l/ldocbeb6f.css';
import '../../css/a/ao01edcje.css';
import '../../css/p/pag9h1bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="ldocbeb6f"/><path class="ao01edcje"/><path class="pag9h1bav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:folders-line" /></template>
