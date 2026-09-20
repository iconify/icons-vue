<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu_tt__st.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu_tt__st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:catalog-filled" /></template>
