<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5o151vba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5o151vba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:gitea" /></template>
