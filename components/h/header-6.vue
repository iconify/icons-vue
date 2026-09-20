<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohcqs1rls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4.5,"top":-7};
const content = `<path class="ohcqs1rls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:header-6" /></template>
