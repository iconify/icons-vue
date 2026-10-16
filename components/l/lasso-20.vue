<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amp6lobmd.css';
import '../../css/t/tcgbwhb4q.css';
import '../../css/m/m-_pn25zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="amp6lobmd"/><path class="tcgbwhb4q"/><path class="m-_pn25zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lasso-20" /></template>
