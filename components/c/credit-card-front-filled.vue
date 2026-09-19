<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqxueobie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqxueobie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:credit-card-front-filled" /></template>
