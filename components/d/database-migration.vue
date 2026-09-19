<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozskazbsp.css';
import '../../css/j/j4z5zmbnn.css';
import '../../css/d/ddvpwkbmt.css';
import '../../css/r/rkqbxubsf.css';
import '../../css/g/g51i94h2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozskazbsp"/><path class="j4z5zmbnn"/><path class="ddvpwkbmt"/><path class="rkqbxubsf"/><path class="g51i94h2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:database-migration" /></template>
