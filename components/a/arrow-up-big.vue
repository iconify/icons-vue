<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck6mx7q6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck6mx7q6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-up-big" /></template>
