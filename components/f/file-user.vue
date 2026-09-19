<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/c73e0yd1g.css';
import '../../css/s/s-37tkb2d.css';
import '../../css/y/ykzxdyblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c73e0yd1g"/><path class="s-37tkb2d"/><path class="ykzxdyblb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-user" /></template>
