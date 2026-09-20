<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beziji2lr.css';
import '../../css/a/a274jortb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="beziji2lr"/><path class="a274jortb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:fluid" /></template>
