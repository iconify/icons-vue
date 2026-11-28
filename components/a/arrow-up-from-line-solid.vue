<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g36qw7qxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g36qw7qxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-up-from-line-solid" /></template>
