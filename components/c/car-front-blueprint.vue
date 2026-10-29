<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/g/grr76eb_c.css';
import '../../css/u/u9i7zubab.css';
import '../../css/n/nge5cfbll.css';
import '../../css/y/y-6gv1b7f.css';
import '../../css/w/wcpe8eb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="grr76eb_c wm-deco"/><path class="u9i7zubab wm-deco"/><path class="nge5cfbll wm-deco"/><path class="wm-k y-6gv1b7f"/><path class="wcpe8eb7b wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:car-front-blueprint" /></template>
