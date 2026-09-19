<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y78brmb1h.css';
import '../../css/e/emc2etbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y78brmb1h"/><path clip-rule="evenodd" class="emc2etbcu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:close-sidebar-alt-solid" /></template>
