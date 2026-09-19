<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4f4nn3zt.css';
import '../../css/c/c25131bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c4f4nn3zt"/><path class="c25131bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-box-double-fill-16" /></template>
