<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peznxynyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="peznxynyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-pull-request-create-arrow-fill" /></template>
