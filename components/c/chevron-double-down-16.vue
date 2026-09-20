<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo9qf5b_i.css';
import '../../css/q/qp7bbshih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lo9qf5b_i"/><path clip-rule="evenodd" class="qp7bbshih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:chevron-double-down-16" /></template>
