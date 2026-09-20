<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lskd2sbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lskd2sbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:jirasoftware" /></template>
