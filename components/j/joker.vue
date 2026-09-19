<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/ltvjxn4rb.css';
import '../../css/j/jazddqb5w.css';
import '../../css/e/enutafbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="ltvjxn4rb"/><path class="jazddqb5w"/><path class="enutafbsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:joker" /></template>
