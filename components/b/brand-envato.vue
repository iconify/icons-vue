<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zunhejbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zunhejbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-envato" /></template>
