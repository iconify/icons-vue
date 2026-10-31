<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9cl-boot.css';
import '../../css/r/rltssxbuj.css';
import '../../css/g/g323dnkch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="l9cl-boot"/><path class="rltssxbuj"/><path class="g323dnkch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:ireland" /></template>
