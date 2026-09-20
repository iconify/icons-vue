<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjxqo3bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjxqo3bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:circle-notch" /></template>
