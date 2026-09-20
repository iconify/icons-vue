<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wism3vaym.css';
import '../../css/k/knur8ibvp.css';
import '../../css/c/cdcnwyb5e.css';
import '../../css/a/akx9uvbtx.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="wism3vaym"/><path class="knur8ibvp"/><path class="cdcnwyb5e"/><path class="akx9uvbtx"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-algeria" /></template>
