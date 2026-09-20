<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s31lv9kcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s31lv9kcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:align-letter-right" /></template>
