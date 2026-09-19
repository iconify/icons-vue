<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7daet4tt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="n7daet4tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:github" /></template>
