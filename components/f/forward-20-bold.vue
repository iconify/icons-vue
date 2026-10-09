<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao5pawu6s.css';
import '../../css/v/v-ad93beh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ao5pawu6s"/><path class="v-ad93beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:forward-20-bold" /></template>
