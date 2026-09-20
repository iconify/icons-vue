<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrlnzc.css';
import '../../css/y/ycz98z.css';
import '../../css/b/botfzx.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-1.css';
import '../../css/t/tr-143p1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGXBl9cdqY"><path class="jrlnzc"/><path class="ycz98z"/></mask></defs><path mask="url(#SVGXBl9cdqY)" class="botfzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:cloud-alt-braces" /></template>
