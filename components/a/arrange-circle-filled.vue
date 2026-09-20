<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdwd_9gor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdwd_9gor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrange-circle-filled" /></template>
