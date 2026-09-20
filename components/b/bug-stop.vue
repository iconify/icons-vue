<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-rd-o6my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-rd-o6my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bug-stop" /></template>
