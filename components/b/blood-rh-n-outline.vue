<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/j852ylbcm.css';
import '../../css/i/im9q6tt0h.css';
import '../../css/z/zs0rlhisk.css';
import '../../css/b/ba90tvb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="j852ylbcm"/><path class="im9q6tt0h"/><path clip-rule="evenodd" class="zs0rlhisk"/><path class="ba90tvb7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-rh-n-outline" /></template>
