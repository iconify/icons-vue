<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rypw29bpx.css';
import '../../css/o/ono4a3f1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rypw29bpx"/><path clip-rule="evenodd" class="ono4a3f1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:comment-minus-outline" /></template>
