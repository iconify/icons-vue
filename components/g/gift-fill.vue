<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrt_g7bic.css';
import '../../css/r/rzcm8fagf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zrt_g7bic"/><path class="rzcm8fagf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:gift-fill" /></template>
