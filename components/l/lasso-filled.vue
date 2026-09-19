<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml5jf-drw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml5jf-drw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:lasso-filled" /></template>
