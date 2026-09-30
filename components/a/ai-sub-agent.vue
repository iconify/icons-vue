<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyaoj4kbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyaoj4kbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:ai-sub-agent" /></template>
