<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqal6abww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jqal6abww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bag-sharp" /></template>
