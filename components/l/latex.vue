<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l911c10ro.css';
import '../../css/o/owjtq1bck.css';
import '../../css/b/bscpnfz0g.css';
import '../../css/n/nr8-grdud.css';
import '../../css/b/bzia22n1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l911c10ro"/><path class="owjtq1bck"/><path class="bscpnfz0g"/><path class="nr8-grdud"/><path class="bzia22n1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:latex" /></template>
