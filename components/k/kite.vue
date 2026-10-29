<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/z275h0bix.css';
import '../../css/s/sh981rb_o.css';
import '../../css/s/smxyi4bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="z275h0bix"/><path class="sh981rb_o wm-a"/><path class="smxyi4bje wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:kite" /></template>
