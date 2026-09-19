<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyl65wiih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b zyl65wiih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:layout-check" /></template>
