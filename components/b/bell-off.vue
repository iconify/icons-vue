<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx5qw-f6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx5qw-f6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:bell-off" /></template>
