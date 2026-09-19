<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jw65pab4k.css';
import '../../css/i/im9q6tt0h.css';
import '../../css/z/zs0rlhisk.css';
import '../../css/b/ba90tvb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="jw65pab4k"/><path class="im9q6tt0h"/><path clip-rule="evenodd" class="zs0rlhisk"/><path class="ba90tvb7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-rh-n" /></template>
