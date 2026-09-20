<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apo15lbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="apo15lbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-up-circle-solid" /></template>
