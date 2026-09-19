<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdms0vy3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="bdms0vy3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:facemask-fill" /></template>
