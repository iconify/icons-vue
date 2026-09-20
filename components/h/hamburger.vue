<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/r/rzc42il7p.css';
import '../../css/x/xeuwd5bbt.css';
import '../../css/h/huilrub5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rzc42il7p"/><rect class="xeuwd5bbt"/><path class="huilrub5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:hamburger" /></template>
