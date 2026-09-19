<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpeepxwiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1217,"height":1000};
const content = `<path class="zpeepxwiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:archive" /></template>
