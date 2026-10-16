<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prpf4nbyc.css';
import '../../css/c/cvgo0ielg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="prpf4nbyc"/><path class="cvgo0ielg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:glacier-20" /></template>
