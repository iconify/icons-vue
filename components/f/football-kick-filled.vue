<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuxwwovsb.css';
import '../../css/b/b6hnulsaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuxwwovsb"/><path class="b6hnulsaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:football-kick-filled" /></template>
