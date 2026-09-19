<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c80hh1xpf.css';
import '../../css/z/ze3pztb9b.css';
import '../../css/q/qnhtqjloi.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="c80hh1xpf clr-i-outline clr-i-outline-path-1"/><path class="clr-i-outline clr-i-outline-path-2 ze3pztb9b"/><path class="clr-i-outline clr-i-outline-path-3 qnhtqjloi"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:code-line" /></template>
