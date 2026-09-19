<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g03z_wayl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g03z_wayl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:folder-x-filled" /></template>
