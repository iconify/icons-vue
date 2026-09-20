<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-5rdijtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-5rdijtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:lightning-off-solid" /></template>
