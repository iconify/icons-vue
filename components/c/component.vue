<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-ck5jrnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-ck5jrnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:component" /></template>
