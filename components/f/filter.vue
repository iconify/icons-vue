<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbeb90ock.css';
import '../../css/h/hmezibw8e.css';
import '../../css/m/mnjrvv75q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbeb90ock wm-k"/><path class="hmezibw8e wm-k"/><path class="mnjrvv75q wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:filter" /></template>
