<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooiusmb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ooiusmb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bag-x-fill" /></template>
