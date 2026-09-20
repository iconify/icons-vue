<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t639_obhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t639_obhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:envelope-lock" /></template>
