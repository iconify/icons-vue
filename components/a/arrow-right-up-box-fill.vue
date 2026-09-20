<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4sx742st.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4sx742st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-right-up-box-fill" /></template>
