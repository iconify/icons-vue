<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v21p3mbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v21p3mbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bnbchain" /></template>
