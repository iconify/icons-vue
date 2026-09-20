<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1yk7ac1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1yk7ac1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:eye-2-fill" /></template>
