<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmhrr5b1v.css';
import '../../css/z/z3v_axe2j.css';
import '../../css/l/lonnihb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vmhrr5b1v"/><path class="z3v_axe2j"/><path class="lonnihb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:cloudrun" /></template>
