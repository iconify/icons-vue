<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/as30jtb7v.css';
import '../../css/u/u9wh36b8p.css';
import '../../css/u/ui5ygsbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="as30jtb7v"/><path class="u9wh36b8p"/><path class="ui5ygsbnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:house-duotone" /></template>
