<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwug5sbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="pwug5sbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:bed" /></template>
