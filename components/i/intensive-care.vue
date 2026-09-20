<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_y2z3b_y.css';
import '../../css/u/ui03rkztx.css';
import '../../css/z/z9vc1bj-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="i_y2z3b_y"/><path class="ui03rkztx"/><path class="z9vc1bj-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:intensive-care" /></template>
