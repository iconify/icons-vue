<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjq_xkura.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjq_xkura"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heading-3" /></template>
