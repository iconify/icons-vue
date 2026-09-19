<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpl9-m38e.css';
import '../../css/w/wrto5cmdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kpl9-m38e"/><path class="wrto5cmdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:error-filled" /></template>
