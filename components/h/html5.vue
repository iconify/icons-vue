<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crhxvtukx.css';
import '../../css/m/m1mw2hbxc.css';
import '../../css/q/q7vfdtbpt.css';
import '../../css/z/z8l5u13up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="crhxvtukx"/><path class="m1mw2hbxc"/><path class="q7vfdtbpt"/><path class="z8l5u13up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:html5" /></template>
