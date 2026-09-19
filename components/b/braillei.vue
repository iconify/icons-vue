<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcdkupb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="pcdkupb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:braillei" /></template>
