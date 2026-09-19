<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl016cbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl016cbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:cube-alt" /></template>
