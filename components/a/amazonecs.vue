<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukg2fabqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukg2fabqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:amazonecs" /></template>
