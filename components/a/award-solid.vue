<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f4hm7m_rz.css';
import '../../css/h/heegwbb3r.css';
import '../../css/z/zv8mbzzst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f4hm7m_rz"/><path clip-rule="evenodd" class="heegwbb3r"/><path class="zv8mbzzst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:award-solid" /></template>
