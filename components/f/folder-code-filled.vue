<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf8xy5bnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf8xy5bnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:folder-code-filled" /></template>
