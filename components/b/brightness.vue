<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqoppnb6n.css';
import '../../css/a/aps6ewwol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqoppnb6n"/><path class="aps6ewwol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:brightness" /></template>
