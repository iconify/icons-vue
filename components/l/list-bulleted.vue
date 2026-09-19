<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfk9ubm9c.css';
import '../../css/x/xe9uj2srj.css';
import '../../css/g/gvyjhvf0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="jfk9ubm9c"/><circle class="xe9uj2srj"/><path class="gvyjhvf0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:list-bulleted" /></template>
