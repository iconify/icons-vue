<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s85i_fbsw.css';
import '../../css/o/ov9g6-b6k.css';
import '../../css/e/eww8hdbpb.css';
import '../../css/l/lbhftjbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="s85i_fbsw"/><path class="ov9g6-b6k"/><path class="eww8hdbpb"/><path class="lbhftjbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:cmake" /></template>
