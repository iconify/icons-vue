<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty0d6cbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty0d6cbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message-alt-detail" /></template>
