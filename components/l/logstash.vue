<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oopsgunny.css';
import '../../css/e/eq6f2obhm.css';
import '../../css/u/uxyj568bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="oopsgunny"/><path class="eq6f2obhm"/><path class="uxyj568bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:logstash" /></template>
