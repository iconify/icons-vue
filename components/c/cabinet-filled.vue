<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql_70zbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql_70zbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cabinet-filled" /></template>
