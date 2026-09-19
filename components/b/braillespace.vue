<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3zir7nhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="l3zir7nhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:braillespace" /></template>
