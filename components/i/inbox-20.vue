<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk9klbblz.css';
import '../../css/j/j8rsm4b8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jk9klbblz"/><path class="j8rsm4b8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:inbox-20" /></template>
