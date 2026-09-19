<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2tgebcxx.css';
import '../../css/b/bd3d8z14l.css';
import '../../css/g/gnu68mb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q2tgebcxx"/><path class="bd3d8z14l"/><path class="gnu68mb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:googlecolab" /></template>
