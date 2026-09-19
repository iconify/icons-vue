<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfri2bcju.css';
import '../../css/a/afytkk3tf.css';
import '../../css/b/b9d8xnfhk.css';
import '../../css/h/h7os9z6mq.css';
import '../../css/t/t3-x66blb.css';
import '../../css/k/kju6qdbte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cfri2bcju"><path class="afytkk3tf"/><path class="b9d8xnfhk"/></g><circle class="h7os9z6mq"/><path class="t3-x66blb"/><path class="kju6qdbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:landscape" /></template>
