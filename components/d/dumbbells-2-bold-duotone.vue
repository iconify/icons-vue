<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzhk1zbhj.css';
import '../../css/a/ann86zbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzhk1zbhj"/><path class="ann86zbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dumbbells-2-bold-duotone" /></template>
