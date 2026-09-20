<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b24-rb27b.css';
import '../../css/f/finxjm9eq.css';
import '../../css/g/gza2rb70b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="b24-rb27b"/><path class="finxjm9eq"/><path class="gza2rb70b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cart-large5-duotone" /></template>
