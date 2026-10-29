<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-4a-kbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-4a-kbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:credit-card-solid" /></template>
