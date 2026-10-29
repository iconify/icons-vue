<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1qt20k5x.css';
import '../../css/c/cnpmqjbkf.css';
import '../../css/n/n1frkeb8b.css';
import '../../css/n/nv6oopddu.css';
import '../../css/w/wj3kfezij.css';
import '../../css/o/oat9a2bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1qt20k5x wm-shadow"/><path class="cnpmqjbkf wm-k"/><path class="n1frkeb8b wm-k"/><path class="nv6oopddu wm-k"/><path class="wj3kfezij wm-k"/><path class="oat9a2bar wm-shine"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:dollar-sign" /></template>
