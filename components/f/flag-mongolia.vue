<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnr7_pc2c.css';
import '../../css/y/yonf7by6s.css';
import '../../css/v/vm46r9bsk.css';
import '../../css/z/zucc7kqxu.css';
import '../../css/y/y5fhatbfs.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="dnr7_pc2c"/><path class="yonf7by6s"/><circle class="vm46r9bsk"/><circle class="zucc7kqxu"/><path class="y5fhatbfs"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-mongolia" /></template>
