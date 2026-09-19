<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux27x7bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux27x7bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:indent-outline" /></template>
