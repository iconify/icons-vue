<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_zl1tdsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="j_zl1tdsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:empty-battery" /></template>
