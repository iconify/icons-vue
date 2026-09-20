<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvwx6gb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvwx6gb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-disability-outline" /></template>
