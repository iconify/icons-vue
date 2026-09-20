<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1ff85b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1ff85b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:guilded" /></template>
