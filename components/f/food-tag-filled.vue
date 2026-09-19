<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5dn81dyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5dn81dyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:food-tag-filled" /></template>
