<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly6ob-bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ly6ob-bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cloud-sun-bolt-fill" /></template>
