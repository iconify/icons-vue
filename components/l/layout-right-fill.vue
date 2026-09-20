<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knj52s_nk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knj52s_nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-right-fill" /></template>
