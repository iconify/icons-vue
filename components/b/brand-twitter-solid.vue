<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dao-jj67u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dao-jj67u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:brand-twitter-solid" /></template>
