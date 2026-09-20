<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a846-ybbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a846-ybbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:blazemeter" /></template>
