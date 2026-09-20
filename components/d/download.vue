<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/giq5sk66w.css';
import '../../css/y/yypjo3b2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="giq5sk66w"/><path class="yypjo3b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:download" /></template>
