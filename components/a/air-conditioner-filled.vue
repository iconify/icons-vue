<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojk8-p4ac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojk8-p4ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:air-conditioner-filled" /></template>
