<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgu_qf8mr.css';
import '../../css/n/nirbr8brm.css';
import '../../css/a/aot_jkqqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="fgu_qf8mr"/><path class="nirbr8brm"/><path class="aot_jkqqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:gabon" /></template>
