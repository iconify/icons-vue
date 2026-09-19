<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsd9cfbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":768};
const content = `<path class="rsd9cfbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:clear" /></template>
