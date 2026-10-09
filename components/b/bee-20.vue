<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac5rx7nmm.css';
import '../../css/l/lts7tcach.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ac5rx7nmm"/><path class="lts7tcach"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bee-20" /></template>
