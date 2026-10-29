<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/c/cl67d3edb.css';
import '../../css/d/d8p35_05q.css';
import '../../css/j/jy1aez1fn.css';
import '../../css/m/mgmiowbmj.css';
import '../../css/j/jcfvhdnpn.css';
import '../../css/f/fk_x1neis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="cl67d3edb wm-deco"/><path class="d8p35_05q wm-deco"/><path class="jy1aez1fn wm-k"/><path class="mgmiowbmj wm-a"/><path class="jcfvhdnpn wm-k"/><path class="fk_x1neis wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:link-blueprint" /></template>
