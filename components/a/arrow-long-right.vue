<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqq-s5bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqq-s5bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrow-long-right" /></template>
