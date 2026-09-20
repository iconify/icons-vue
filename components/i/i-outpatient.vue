<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqbik8bfl.css';
import '../../css/y/y3bjwfy8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="eqbik8bfl"/><path class="y3bjwfy8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-outpatient" /></template>
