<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky2eltbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ky2eltbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:image-inverted" /></template>
