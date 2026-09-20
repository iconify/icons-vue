<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/valyeabbz.css';
import '../../css/i/i2uv34b7c.css';
import '../../css/a/apw8bcc0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="valyeabbz"/><path class="i2uv34b7c"/><path clip-rule="evenodd" class="apw8bcc0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:crown" /></template>
