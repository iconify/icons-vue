<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrlnzc.css';
import '../../css/y/ymaqmw.css';
import '../../css/b/botfzx.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-1.css';
import '../../css/d/d-1mdu6d.css';
import '../../css/d/d-360tni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGcoProd2D"><path class="jrlnzc"/><path class="ymaqmw"/></mask></defs><path mask="url(#SVGcoProd2D)" class="botfzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:cloud-alt-download-filled" /></template>
