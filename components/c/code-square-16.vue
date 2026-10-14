<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv2r58bup.css';
import '../../css/n/nz-7s6boo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lv2r58bup"/><path class="nz-7s6boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:code-square-16" /></template>
