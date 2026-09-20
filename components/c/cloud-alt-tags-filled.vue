<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gutzyv.css';
import '../../css/t/t5pxry.css';
import '../../css/m/m9-8qf.css';
import '../../css/b/botfzx.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-1.css';
import '../../css/f/fade-to-1.css';
import '../../css/s/so-from-8.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGlJj8Tdyp"><path class="gutzyv t5pxry"/><path class="m9-8qf t5pxry"/></mask></defs><path mask="url(#SVGlJj8Tdyp)" class="botfzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:cloud-alt-tags-filled" /></template>
