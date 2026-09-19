<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfwp58bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfwp58bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-uturn-up" /></template>
