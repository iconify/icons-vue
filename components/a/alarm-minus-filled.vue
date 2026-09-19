<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbyhpqj2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbyhpqj2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alarm-minus-filled" /></template>
