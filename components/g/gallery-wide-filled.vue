<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s5g_42bun.css';
import '../../css/b/b0k0uuwhg.css';
import '../../css/n/neqh-tgow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s5g_42bun"/><path clip-rule="evenodd" class="b0k0uuwhg"/><path class="neqh-tgow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gallery-wide-filled" /></template>
