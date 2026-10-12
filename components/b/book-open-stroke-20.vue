<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln0p78bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ln0p78bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:book-open-stroke-20" /></template>
