<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvyy1sb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvyy1sb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-bottombar-expand-filled" /></template>
