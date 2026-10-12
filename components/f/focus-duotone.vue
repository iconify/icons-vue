<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f29fwjbso.css';
import '../../css/j/jyuddqs9y.css';
import '../../css/a/apz-hktzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f29fwjbso"/><path class="jyuddqs9y"/><path class="apz-hktzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:focus-duotone" /></template>
