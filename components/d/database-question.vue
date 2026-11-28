<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5fe-rb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5fe-rb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:database-question" /></template>
