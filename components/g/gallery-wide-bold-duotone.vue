<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ugtn2gb9g.css';
import '../../css/i/i3289rbus.css';
import '../../css/l/lsbtr9k-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ugtn2gb9g"/><path clip-rule="evenodd" class="i3289rbus"/><path class="lsbtr9k-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-wide-bold-duotone" /></template>
