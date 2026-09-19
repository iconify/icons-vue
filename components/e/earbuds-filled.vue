<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn4hukbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn4hukbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:earbuds-filled" /></template>
