<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqss8kh_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":441,"height":512};
const content = `<path class="tqss8kh_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:frege" /></template>
