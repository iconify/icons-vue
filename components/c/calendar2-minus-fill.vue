<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znt2fn3zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="znt2fn3zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:calendar2-minus-fill" /></template>
