<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_ct1ubvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_ct1ubvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:capsule" /></template>
