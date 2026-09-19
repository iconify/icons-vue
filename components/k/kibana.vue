<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfdq1hqyb.css';
import '../../css/b/b_1t8ab1f.css';
import '../../css/p/pu2xhg2fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kfdq1hqyb"/><path class="b_1t8ab1f"/><path class="pu2xhg2fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:kibana" /></template>
