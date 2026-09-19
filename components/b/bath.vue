<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo0om22dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo0om22dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bath" /></template>
