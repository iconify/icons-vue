<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/d/dn1pzokyp.css';
import '../../css/t/tq0y-p-0s.css';
import '../../css/a/ajqhpcbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dn1pzokyp"/><path class="tq0y-p-0s"/><path class="ajqhpcbca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:calendar-remove" /></template>
