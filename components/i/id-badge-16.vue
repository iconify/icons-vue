<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbh-40nht.css';
import '../../css/j/jze6f0ytj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lbh-40nht"/><path class="jze6f0ytj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:id-badge-16" /></template>
