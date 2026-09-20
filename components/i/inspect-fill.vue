<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv15p9qut.css';
import '../../css/t/tytb7gbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv15p9qut"/><path class="tytb7gbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:inspect-fill" /></template>
