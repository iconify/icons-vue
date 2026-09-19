<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glo9mrbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glo9mrbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:briefcase-alt-2" /></template>
