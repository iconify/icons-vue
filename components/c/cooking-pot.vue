<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezc6i445w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezc6i445w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cooking-pot" /></template>
