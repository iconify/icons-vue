<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zg5a7jb0o.css';
import '../../css/h/h6f3a38bp.css';
import '../../css/g/g02vaqb7b.css';
import '../../css/y/ygtalcb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="zg5a7jb0o"/><path class="h6f3a38bp wm-k"/><path class="g02vaqb7b wm-k"/><path class="wm-a ygtalcb8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lightbulb-sketch" /></template>
