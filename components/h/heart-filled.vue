<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn1ghtb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn1ghtb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:heart-filled" /></template>
