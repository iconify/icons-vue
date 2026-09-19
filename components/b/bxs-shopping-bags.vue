<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdznddjex.css';
import '../../css/n/n4fvzrmzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdznddjex"/><path class="n4fvzrmzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-shopping-bags" /></template>
