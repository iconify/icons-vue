<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tr5gqzbjx.css';
import '../../css/m/m9wqefbui.css';
import '../../css/c/c2qsnhb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="tr5gqzbjx"/><path class="m9wqefbui"/><path class="c2qsnhb3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:film-1-bold" /></template>
