<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_x3e4-7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b_x3e4-7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:indent-20-solid" /></template>
