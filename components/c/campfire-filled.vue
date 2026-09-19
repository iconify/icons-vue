<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kti4eo0qw.css';
import '../../css/n/n7mu1nbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kti4eo0qw"/><path class="n7mu1nbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:campfire-filled" /></template>
