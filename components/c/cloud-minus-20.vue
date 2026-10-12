<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjuk3kbct.css';
import '../../css/g/gr80gyb-f.css';
import '../../css/a/a--uzxbtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hjuk3kbct"/><path class="gr80gyb-f"/><path class="a--uzxbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-minus-20" /></template>
