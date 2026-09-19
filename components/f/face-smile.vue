<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5hig7ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="i5hig7ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:face-smile" /></template>
