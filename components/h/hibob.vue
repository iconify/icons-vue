<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbo6n2bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbo6n2bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hibob" /></template>
