<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcn8ucyih.css';
import '../../css/j/j62e8oyno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bcn8ucyih"/><path class="j62e8oyno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:lightning" /></template>
