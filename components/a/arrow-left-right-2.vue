<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp3su_b5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp3su_b5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-left-right-2" /></template>
