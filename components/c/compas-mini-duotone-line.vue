<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o58hkebvg.css';
import '../../css/x/xjghu547v.css';
import '../../css/b/btizuutzp.css';
import '../../css/w/w49j0rbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGfvUskeMK"><g class="o58hkebvg"><path class="xjghu547v"/><circle class="btizuutzp"/></g></mask></defs><path mask="url(#SVGfvUskeMK)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:compas-mini-duotone-line" /></template>
