<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx1fsfbvz.css';
import '../../css/k/kj930pbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx1fsfbvz"/><path class="kj930pbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-window-open" /></template>
