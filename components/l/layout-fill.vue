<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzaucew7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzaucew7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-fill" /></template>
