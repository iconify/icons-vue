<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uro-57cwo.css';
import '../../css/t/tug3bsbqm.css';
import '../../css/d/de9pw2bhz.css';
import '../../css/l/lg6s08b8i.css';
import '../../css/b/b4pp4n9kw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uro-57cwo wm-k"/><path class="tug3bsbqm wm-shine"/><path class="de9pw2bhz wm-shine"/><path class="lg6s08b8i wm-shine"/><path class="b4pp4n9kw wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:avatar-dino" /></template>
