<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh74e8blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jh74e8blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:github-o" /></template>
