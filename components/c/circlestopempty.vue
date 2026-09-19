<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpmpq7j_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jpmpq7j_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circlestopempty" /></template>
