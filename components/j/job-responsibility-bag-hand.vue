<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcsvxunqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcsvxunqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:job-responsibility-bag-hand" /></template>
