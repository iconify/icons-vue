<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8wg0cc7n.css';
import '../../css/r/r_s901bbt.css';
import '../../css/y/yp1ozz1bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8wg0cc7n"/><path class="r_s901bbt"/><path class="yp1ozz1bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:automl-tables" /></template>
