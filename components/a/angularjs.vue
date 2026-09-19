<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9gw86b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="h9gw86b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:angularjs" /></template>
