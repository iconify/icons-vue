<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiy_jr2tf.css';
import '../../css/a/azjswrsrh.css';
import '../../css/n/n9w5lobwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jiy_jr2tf"/><path class="azjswrsrh"/><path class="n9w5lobwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:grc" /></template>
