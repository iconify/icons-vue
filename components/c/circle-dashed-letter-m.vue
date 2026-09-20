<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn_jkz6ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn_jkz6ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-letter-m" /></template>
