<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1zz_mb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1zz_mb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-down-box-fill" /></template>
