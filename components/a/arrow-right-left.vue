<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9mei8bbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9mei8bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:arrow-right-left" /></template>
