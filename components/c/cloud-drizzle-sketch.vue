<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/h15jcwwia.css';
import '../../css/p/prpj5j7se.css';
import '../../css/b/byvjrw0sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="h15jcwwia"/><path class="prpj5j7se wm-k"/><path class="byvjrw0sk wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-drizzle-sketch" /></template>
