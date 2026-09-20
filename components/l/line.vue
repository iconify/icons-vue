<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqpw6snrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqpw6snrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:line" /></template>
