<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p9lqnjuwa.css';
import '../../css/v/v7wgf53bu.css';
import '../../css/i/iohxa7xbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="p9lqnjuwa"/><path clip-rule="evenodd" class="v7wgf53bu"/><path clip-rule="evenodd" class="iohxa7xbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:logo-yandex-id" /></template>
