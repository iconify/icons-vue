<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi-0iegqa.css';
import '../../css/o/o-nkwpb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="mi-0iegqa"/><path class="o-nkwpb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:administration" /></template>
