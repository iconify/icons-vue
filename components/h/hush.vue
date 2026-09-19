<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/v/v4cdqwbvw.css';
import '../../css/v/v4vk_jbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="v4cdqwbvw"/><path class="v4vk_jbvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:hush" /></template>
