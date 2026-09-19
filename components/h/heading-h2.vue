<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwm6jac9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwm6jac9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:heading-h2" /></template>
