<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rb_6zxbcl.css';
import '../../css/u/u2gjaigap.css';
import '../../css/m/mvn6bybtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="rb_6zxbcl"/><path class="u2gjaigap"/><path class="mvn6bybtl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:card-search-filled" /></template>
