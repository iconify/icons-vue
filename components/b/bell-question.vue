<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyq89wxfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyq89wxfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-question" /></template>
