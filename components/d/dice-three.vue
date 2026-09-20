<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0-k_j9dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0-k_j9dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:dice-three" /></template>
