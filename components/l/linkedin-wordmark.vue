<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_7p37bmf.css';
import '../../css/l/ly5qkx5wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="k_7p37bmf"/><path class="ly5qkx5wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:linkedin-wordmark" /></template>
