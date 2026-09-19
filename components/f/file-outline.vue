<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa3_kk4st.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa3_kk4st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-outline" /></template>
