<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c80hh1xpf.css';
import '../../css/z/ze3pztb9b.css';
import '../../css/q/qnhtqjloi.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="c80hh1xpf clr-i-outline--badged clr-i-outline-path-1--badged"/><path class="clr-i-outline--badged clr-i-outline-path-2--badged ze3pztb9b"/><path class="clr-i-outline--badged clr-i-outline-path-3--badged qnhtqjloi"/><circle class="clr-i-badge clr-i-outline--badged clr-i-outline-path-4--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:code-outline-badged" /></template>
