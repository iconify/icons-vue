<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk0kgkwuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk0kgkwuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:flag-2-filled" /></template>
