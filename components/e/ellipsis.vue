<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnq2q5bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gnq2q5bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:ellipsis" /></template>
