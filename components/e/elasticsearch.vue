<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig88j0zen.css';
import '../../css/d/d6l1v3bwk.css';
import '../../css/o/o5u_ysb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ig88j0zen"/><path class="d6l1v3bwk"/><path class="o5u_ysb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:elasticsearch" /></template>
