<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo6e8nbzk.css';
import '../../css/z/zhe7nq6ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo6e8nbzk"/><path class="zhe7nq6ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:institution" /></template>
