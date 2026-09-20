<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo30i31yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo30i31yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:lightning-slash-solid" /></template>
