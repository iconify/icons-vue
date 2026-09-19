<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvf4-gbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="jvf4-gbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:home-fill-26" /></template>
