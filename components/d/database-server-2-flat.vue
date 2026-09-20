<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/b0z4htqyr.css';
import '../../css/x/xbrdrg5rk.css';
import '../../css/h/hrb6kyb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="b0z4htqyr"/><path class="xbrdrg5rk"/><path class="hrb6kyb2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:database-server-2-flat" /></template>
