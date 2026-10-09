<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-l-y7baz.css';
import '../../css/c/cnp57_zxn.css';
import '../../css/j/jlvwd6bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k-l-y7baz"/><path class="cnp57_zxn"/><path class="jlvwd6bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:archive-20-bold" /></template>
