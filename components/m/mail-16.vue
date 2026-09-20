<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a79_kzbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a79_kzbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:mail-16" /></template>
