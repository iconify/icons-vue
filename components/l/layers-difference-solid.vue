<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td1zipb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="td1zipb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:layers-difference-solid" /></template>
