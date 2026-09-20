<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjlzt-g3f.css';
import '../../css/t/t5c3kxbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="gjlzt-g3f"/><path class="t5c3kxbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:arrow-left" /></template>
