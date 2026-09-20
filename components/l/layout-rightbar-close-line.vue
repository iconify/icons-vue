<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9db1vhft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9db1vhft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-rightbar-close-line" /></template>
