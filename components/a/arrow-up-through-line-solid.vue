<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cud7f3biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cud7f3biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-up-through-line-solid" /></template>
