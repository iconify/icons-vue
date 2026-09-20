<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ut32ur4ud.css';
import '../../css/b/b17u35b3a.css';
import '../../css/o/o8qkkzbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ut32ur4ud"/><path class="b17u35b3a"/><path class="o8qkkzbki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:coin-filled" /></template>
