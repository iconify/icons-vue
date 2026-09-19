<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8-e8acbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8-e8acbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:eye-off" /></template>
