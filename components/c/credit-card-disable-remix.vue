<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd2-fnpdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jd2-fnpdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:credit-card-disable-remix" /></template>
