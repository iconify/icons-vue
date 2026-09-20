<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9-_0pbhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-7,"top":-2};
const content = `<path class="u9-_0pbhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:bottle" /></template>
