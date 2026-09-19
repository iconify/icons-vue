<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfy2lccxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfy2lccxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:christianity-filled" /></template>
