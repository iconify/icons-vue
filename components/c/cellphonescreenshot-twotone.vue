<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/izxv9-bde.css';
import '../../css/g/gz3zk9b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path fill-opacity="0" class="izxv9-bde"><animate fill="freeze" attributeName="stroke-dashoffset" dur="0.6s" values="66;0"/><animate fill="freeze" attributeName="fill-opacity" begin="0.9s" dur="0.15s" to=".3"/></path><path d="M6 2h12v0h-12ZM6 22h12v0h-12Z"><animate fill="freeze" attributeName="d" begin="0.6s" dur="0.2s" to="M6 2h12v3h-12ZM6 22h12v-3h-12Z"/></path></g><path stroke-dashoffset="4" class="gz3zk9b4c"><animate fill="freeze" attributeName="stroke-dashoffset" begin="1.15s" dur="0.2s" to="0"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:cellphonescreenshot-twotone" /></template>
