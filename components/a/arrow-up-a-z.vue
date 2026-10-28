<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjpr_6-3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjpr_6-3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-up-a-z" /></template>
