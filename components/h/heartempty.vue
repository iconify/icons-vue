<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpjoh6btf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":668};
const content = `<path class="zpjoh6btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:heartempty" /></template>
