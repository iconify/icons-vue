<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmjp0wy6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmjp0wy6f primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-double-left-duotone" /></template>
