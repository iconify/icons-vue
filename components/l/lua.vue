<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj_t_y_1r.css';
import '../../css/l/lm83njutd.css';
import '../../css/a/a1qgftbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dj_t_y_1r"/><path class="lm83njutd"/><path class="a1qgftbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:lua" /></template>
