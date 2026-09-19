<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jet9moexx.css';
import '../../css/k/knjswsrwz.css';
import '../../css/b/bql6r7x-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jet9moexx"/><path class="knjswsrwz"/><path class="bql6r7x-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:dataspell-wordmark" /></template>
