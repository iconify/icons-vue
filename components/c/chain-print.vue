<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/a/ax_d6n52x.css';
import '../../css/c/ci92hfguw.css';
import '../../css/r/r50cn1ynh.css';
import '../../css/b/b9ikz88gw.css';
import '../../css/i/i9c9_pwct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="pr52f_b5y"><g class="ax_d6n52x"><rect transform="rotate(33.038 14.784 3.384)" class="ci92hfguw"/><rect transform="rotate(33.038 9.836 7.323)" class="r50cn1ynh"/></g><rect transform="rotate(33.038 13.137 1.192)" class="b9ikz88gw"/><rect transform="rotate(33.038 8.189 5.131)" class="i9c9_pwct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:chain-print" /></template>
