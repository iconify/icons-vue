<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7c6_u3ej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7c6_u3ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:caret-down-filled" /></template>
