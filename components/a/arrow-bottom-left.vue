<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoy1df99u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eoy1df99u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-bottom-left" /></template>
