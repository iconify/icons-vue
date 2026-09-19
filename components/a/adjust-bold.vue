<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/da1skdh9u.css';
import '../../css/l/l958i55ae.css';
import '../../css/c/cyk_bcwer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="da1skdh9u"/><path class="l958i55ae"/><path class="cyk_bcwer"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:adjust-bold" /></template>
