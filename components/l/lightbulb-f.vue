<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_j-4i_al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-1.5};
const content = `<path class="c_j-4i_al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:lightbulb-f" /></template>
