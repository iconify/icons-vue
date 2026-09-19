<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byawaojep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="byawaojep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:list-ol" /></template>
