<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpqhj5bej.css';
import '../../css/x/xe9aj_lzj.css';
import '../../css/p/p_ziwabsz.css';
import '../../css/a/axq3e3bkb.css';
import '../../css/n/nizlai9po.css';
import '../../css/b/bsbdzxd2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gpqhj5bej"/><path class="xe9aj_lzj"/><path class="p_ziwabsz"/><path class="axq3e3bkb"/><path class="nizlai9po"/><path class="bsbdzxd2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:elm" /></template>
