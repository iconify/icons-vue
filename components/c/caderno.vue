<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di5_344sf.css';
import '../../css/j/jpo8em2jn.css';
import '../../css/k/k5xw5glig.css';
import '../../css/g/g62l6wbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="di5_344sf"/><path class="jpo8em2jn"/><path class="k5xw5glig"/><path class="g62l6wbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:caderno" /></template>
