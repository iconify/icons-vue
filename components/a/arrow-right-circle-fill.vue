<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnmqinbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gnmqinbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:arrow-right-circle-fill" /></template>
