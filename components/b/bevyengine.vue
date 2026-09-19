<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-vwe2b6w.css';
import '../../css/f/fzp2tmx2o.css';
import '../../css/a/a6-7rqb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="e-vwe2b6w"/><path class="fzp2tmx2o"/><path class="a6-7rqb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:bevyengine" /></template>
