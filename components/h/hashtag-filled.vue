<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9k5yp1vf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9k5yp1vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:hashtag-filled" /></template>
