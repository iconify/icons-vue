<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h98jf29aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h98jf29aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:carets-right-left-filled" /></template>
