<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4zdesjys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4zdesjys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:lock-access" /></template>
