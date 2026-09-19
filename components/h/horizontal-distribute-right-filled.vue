<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3hxb00gr.css';
import '../../css/c/c2uptobfq.css';
import '../../css/n/nlryl0bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3hxb00gr"/><rect class="c2uptobfq"/><rect class="nlryl0bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:horizontal-distribute-right-filled" /></template>
