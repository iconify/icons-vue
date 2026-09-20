<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq4k1jupl.css';
import '../../css/o/ono_5mbbv.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/o/ol_i9na6a.css';
import '../../css/x/xs4jwd4jb.css';
import '../../css/l/lyuiso92d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="bq4k1jupl"/><path class="ono_5mbbv"/><g class="jn8qy4bru"><path class="ol_i9na6a"/><path class="xs4jwd4jb"/><path class="lyuiso92d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:bacon" /></template>
