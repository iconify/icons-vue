<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdk6zdbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdk6zdbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:department-store-filled" /></template>
