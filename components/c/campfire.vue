<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbiu97owb.css';
import '../../css/k/kti4eo0qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbiu97owb"/><path class="kti4eo0qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:campfire" /></template>
