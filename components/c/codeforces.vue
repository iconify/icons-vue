<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9j15gb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9j15gb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:codeforces" /></template>
