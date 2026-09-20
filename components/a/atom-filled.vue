<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bjxt11j3n.css';
import '../../css/k/kmejg72ch.css';
import '../../css/k/kkj8cetyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bjxt11j3n"/><path clip-rule="evenodd" class="kmejg72ch"/><path class="kkj8cetyt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:atom-filled" /></template>
