<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcfqgs_zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":580,"height":850};
const content = `<path class="rcfqgs_zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:bucket" /></template>
