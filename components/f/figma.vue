<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4028-b3r.css';
import '../../css/t/t5s8-fwfl.css';
import '../../css/a/a6rpd8c1i.css';
import '../../css/d/dyerjlb6g.css';
import '../../css/b/bcl51zb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="i4028-b3r"/><path class="t5s8-fwfl"/><path class="a6rpd8c1i"/><path class="dyerjlb6g"/><path class="bcl51zb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:figma" /></template>
