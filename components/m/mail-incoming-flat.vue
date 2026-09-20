<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/m_dkvxy7f.css';
import '../../css/m/m91w3qb8n.css';
import '../../css/u/u4-0twl4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="m_dkvxy7f"/><path class="m91w3qb8n"/><path class="u4-0twl4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:mail-incoming-flat" /></template>
