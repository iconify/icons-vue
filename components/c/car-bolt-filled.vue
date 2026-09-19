<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5cr_nptn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5cr_nptn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:car-bolt-filled" /></template>
