<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9jb7t68i.css';
import '../../css/r/ri50dbckk.css';
import '../../css/b/bik43675b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q9jb7t68i"/><path class="ri50dbckk"/><path class="bik43675b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:environment-twotone" /></template>
