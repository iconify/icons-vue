<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6lvqji4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6lvqji4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-2-fill" /></template>
