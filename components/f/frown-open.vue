<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpaej3bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="tpaej3bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:frown-open" /></template>
