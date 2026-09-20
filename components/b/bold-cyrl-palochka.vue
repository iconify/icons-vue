<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt6-dubor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tt6-dubor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:bold-cyrl-palochka" /></template>
