<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yktm7h6-w.css';
import '../../css/j/jyold6wus.css';
import '../../css/b/b671z779q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yktm7h6-w"/><path class="jyold6wus"/><path class="b671z779q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fava" /></template>
