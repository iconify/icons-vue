<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnp2z7g5d.css';
import '../../css/x/x-w7n4-xc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hnp2z7g5d"/><path class="x-w7n4-xc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:book-bookmark-filled" /></template>
