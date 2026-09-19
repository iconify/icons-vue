<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgrkbtbto.css';
import '../../css/b/bdumtbccb.css';
import '../../css/d/de-emhyyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgrkbtbto"/><path class="bdumtbccb"/><path class="de-emhyyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:background-tasks" /></template>
