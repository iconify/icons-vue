<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0q8p-bqq.css';
import '../../css/n/n5-1bobdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x0q8p-bqq"/><path class="n5-1bobdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hanger-bold-duotone" /></template>
