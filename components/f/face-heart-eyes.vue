<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju4ghls-w.css';
import '../../css/a/aegljw1gn.css';
import '../../css/c/c5qc64bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju4ghls-w"/><path class="aegljw1gn"/><path class="c5qc64bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:face-heart-eyes" /></template>
