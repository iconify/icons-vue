<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn_zxdbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jn_zxdbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ballerina-wordmark" /></template>
