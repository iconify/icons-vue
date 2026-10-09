<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjudu5_8t.css';
import '../../css/a/a5e9wp-or.css';
import '../../css/h/h7f8bvbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zjudu5_8t"/><path class="a5e9wp-or"/><path class="h7f8bvbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chicken-leg-48-bold" /></template>
